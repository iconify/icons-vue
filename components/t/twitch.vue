<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufj9n4bfr.css';
import '../../css/p/pv04-_f7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufj9n4bfr"/><path class="pv04-_f7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:twitch" /></template>
