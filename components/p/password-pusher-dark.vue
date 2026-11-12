<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jklz1kt1b.css';
import '../../css/i/ianhxwbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jklz1kt1b"/><path class="ianhxwbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:password-pusher-dark" /></template>
