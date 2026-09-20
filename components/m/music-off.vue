<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzuptbcqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzuptbcqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-off" /></template>
