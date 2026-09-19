<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p86nkixdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p86nkixdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:nextcloud" /></template>
