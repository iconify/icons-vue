<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4nb21bnx.css';
import '../../css/d/dj-d89b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s4nb21bnx"/><path class="dj-d89b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nakama-light" /></template>
