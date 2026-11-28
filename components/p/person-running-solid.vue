<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejxfu7bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejxfu7bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:person-running-solid" /></template>
