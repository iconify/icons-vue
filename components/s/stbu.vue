<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx-jwkb3l.css';
import '../../css/a/ackwpdbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx-jwkb3l"/><path class="ackwpdbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:stbu" /></template>
