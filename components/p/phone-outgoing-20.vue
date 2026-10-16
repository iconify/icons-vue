<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2m65bbab.css';
import '../../css/u/uza837t1m.css';
import '../../css/a/an5pwtbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f2m65bbab"/><path class="uza837t1m"/><path class="an5pwtbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-outgoing-20" /></template>
