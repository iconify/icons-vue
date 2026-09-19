<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn6csrh5o.css';
import '../../css/c/cpg14cc3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sn6csrh5o"/><path class="cpg14cc3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:share-boxed" /></template>
