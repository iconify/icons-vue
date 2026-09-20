<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg0i-6tnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg0i-6tnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:paragraph" /></template>
