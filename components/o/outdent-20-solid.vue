<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p477_fbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p477_fbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:outdent-20-solid" /></template>
