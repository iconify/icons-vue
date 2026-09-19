<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gum-icegm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gum-icegm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speech-balloon-small-filled" /></template>
