<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak3yqactp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak3yqactp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:newspaper-solid" /></template>
