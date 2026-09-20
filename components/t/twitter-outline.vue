<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzz6lvbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kzz6lvbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:twitter-outline" /></template>
