<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je0d-9t6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="je0d-9t6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:simplelogin-light" /></template>
