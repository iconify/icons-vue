<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcjnycbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rcjnycbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yandex" /></template>
