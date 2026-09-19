<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szn9f3b9w.css';
import '../../css/l/lr01kmbcw.css';
import '../../css/n/nluribbnp.css';
import '../../css/n/ngct_37bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="szn9f3b9w"/><path class="lr01kmbcw"/><path class="nluribbnp"/><path class="ngct_37bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sunriseovermountains" /></template>
