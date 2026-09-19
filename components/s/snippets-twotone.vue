<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adgvc8bku.css';
import '../../css/f/fw0ks3bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="adgvc8bku"/><path class="fw0ks3bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:snippets-twotone" /></template>
