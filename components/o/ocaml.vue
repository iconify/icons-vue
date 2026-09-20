<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsfdawbzr.css';
import '../../css/s/sghc7ijwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsfdawbzr"/><path class="sghc7ijwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ocaml" /></template>
