<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf_am2bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":460,"height":512};
const content = `<path class="cf_am2bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mruby" /></template>
