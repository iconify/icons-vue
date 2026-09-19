<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1ch7ybkg.css';
import '../../css/t/tqb_6nb6c.css';
import '../../css/i/i7jv4xbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f1ch7ybkg"/><circle class="tqb_6nb6c"/><circle class="i7jv4xbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:more-one" /></template>
