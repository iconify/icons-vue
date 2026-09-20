<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk9zn-beg.css';
import '../../css/o/o9cgf80vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bk9zn-beg"/><path class="o9cgf80vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rauthy-dark" /></template>
