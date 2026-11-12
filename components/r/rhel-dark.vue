<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vug20nb6u.css';
import '../../css/c/cfm66s3uf.css';
import '../../css/b/bfjbb2-nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vug20nb6u"/><path class="cfm66s3uf"/><path class="bfjbb2-nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rhel-dark" /></template>
