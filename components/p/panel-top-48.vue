<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3q6uacna.css';
import '../../css/l/ls72cy7ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v3q6uacna"/><path class="ls72cy7ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-top-48" /></template>
