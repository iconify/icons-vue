<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4nz665xn.css';
import '../../css/b/b6dmwqarl.css';
import '../../css/b/bwdyegfbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a4nz665xn"/><path class="b6dmwqarl"/><path class="bwdyegfbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marp-dark" /></template>
