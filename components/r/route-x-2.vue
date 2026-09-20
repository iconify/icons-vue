<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc49-kpvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc49-kpvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:route-x-2" /></template>
