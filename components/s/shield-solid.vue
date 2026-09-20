<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3rd5ebba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3rd5ebba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-solid" /></template>
