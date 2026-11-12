<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rld-_ccic.css';
import '../../css/f/fkh3zlqaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rld-_ccic"/><path class="fkh3zlqaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sipeed" /></template>
