<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk0m0jtxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sk0m0jtxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:ok-hand-sign-small" /></template>
