<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs6krb0lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs6krb0lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:zoom-in-line" /></template>
