<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggsig13zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ggsig13zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:photo-plus-20-solid" /></template>
