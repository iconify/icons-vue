<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwuzebcck.css';
import '../../css/e/ey9o68b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwuzebcck"/><path class="ey9o68b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:megaphone-duotone" /></template>
