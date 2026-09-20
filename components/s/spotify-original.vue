<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk2j-_b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bk2j-_b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:spotify-original" /></template>
