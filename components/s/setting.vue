<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el40c3ckw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="el40c3ckw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:setting" /></template>
