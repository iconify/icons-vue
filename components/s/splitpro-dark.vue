<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxxgysbnp.css';
import '../../css/p/pn9m9wb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pxxgysbnp"/><path class="pn9m9wb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:splitpro-dark" /></template>
