<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kylfzebuf.css';
import '../../css/i/impgh8bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kylfzebuf"/><path class="impgh8bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pack-light" /></template>
