<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_vtsxbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="v_vtsxbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:map-pin-slash-20-solid" /></template>
