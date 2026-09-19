<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsbivur_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="bsbivur_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:sass" /></template>
