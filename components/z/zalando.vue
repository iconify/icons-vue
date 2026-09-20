<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqrrfm5ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqrrfm5ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zalando" /></template>
