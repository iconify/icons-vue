<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b797wabdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b797wabdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:plesk" /></template>
