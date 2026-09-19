<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd29xjbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pd29xjbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-ordn-small-filled" /></template>
