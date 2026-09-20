<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvg-fypjl.css';
import '../../css/i/i72_7ab1r.css';
import '../../css/f/feqtfmb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvg-fypjl"/><path class="i72_7ab1r"/><path class="feqtfmb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:touch-id-fingerprint-square" /></template>
