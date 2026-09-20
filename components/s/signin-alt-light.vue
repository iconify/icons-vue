<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjckms-gm.css';
import '../../css/w/wpmkoacem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjckms-gm"/><path class="wpmkoacem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:signin-alt-light" /></template>
