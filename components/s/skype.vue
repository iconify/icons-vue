<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijkhwubvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":999.978,"height":1000};
const content = `<path class="ijkhwubvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:skype" /></template>
