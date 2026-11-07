<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmxa02b4w.css';
import '../../css/t/tllmdybix.css';
import '../../css/o/ojkge583k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xmxa02b4w"/><path class="tllmdybix"/><path class="ojkge583k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-heart-bold-duotone" /></template>
