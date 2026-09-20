<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el2kicbta.css';
import '../../css/f/fs0bxbjar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="el2kicbta"/><path class="fs0bxbjar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-talk" /></template>
