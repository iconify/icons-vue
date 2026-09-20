<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e61n9-bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e61n9-bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:openjdk" /></template>
