<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6oo7nb8e.css';
import '../../css/p/phxmbeb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a6oo7nb8e"/><path class="phxmbeb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pomerium-dark" /></template>
