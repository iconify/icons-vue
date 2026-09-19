<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6lfs7i_j.css';
import '../../css/n/n-t7iwbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6lfs7i_j"/><path class="n-t7iwbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-star" /></template>
