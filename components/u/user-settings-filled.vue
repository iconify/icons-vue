<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6_pbfbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a6_pbfbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-settings-filled" /></template>
