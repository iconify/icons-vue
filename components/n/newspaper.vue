<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbq-4rbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbq-4rbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:newspaper" /></template>
