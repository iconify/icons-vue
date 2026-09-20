<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu14mdo9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yu14mdo9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:upload-4" /></template>
