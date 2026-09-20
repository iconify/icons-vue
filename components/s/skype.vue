<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc7043brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bc7043brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:skype" /></template>
