<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4otdk7by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h4otdk7by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-boarding-taxi" /></template>
