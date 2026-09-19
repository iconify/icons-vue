<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3j2idb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s3j2idb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mailbox" /></template>
