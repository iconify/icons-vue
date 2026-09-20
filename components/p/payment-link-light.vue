<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojbic-t7m.css';
import '../../css/p/p5vtv8brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojbic-t7m"/><path class="p5vtv8brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:payment-link-light" /></template>
