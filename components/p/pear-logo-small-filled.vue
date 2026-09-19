<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjc4c_b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rjc4c_b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:pear-logo-small-filled" /></template>
