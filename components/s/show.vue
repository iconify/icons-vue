<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spb-dpbsw.css';
import '../../css/i/ilmvj-v8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spb-dpbsw"/><path class="ilmvj-v8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:show" /></template>
