<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7p8u_bgx.css';
import '../../css/t/t2z2jnber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7p8u_bgx"/><path class="t2z2jnber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pause-duotone" /></template>
