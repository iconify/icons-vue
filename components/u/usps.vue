<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apnc5byip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apnc5byip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:usps" /></template>
