<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8n3hpqxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t8n3hpqxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:minutemailer" /></template>
