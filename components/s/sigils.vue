<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhvpwjd-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhvpwjd-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sigils" /></template>
