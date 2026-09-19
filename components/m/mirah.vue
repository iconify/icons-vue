<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go71j8bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":311,"height":512};
const content = `<path class="go71j8bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mirah" /></template>
