<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k26wlw6el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="k26wlw6el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:video" /></template>
