<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiq_k3ghp.css';
import '../../css/p/psisj8b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fiq_k3ghp"/><path class="psisj8b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:vinyl-record-player-bold" /></template>
