<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqw05nt-o.css';
import '../../css/c/cqbk9ybmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pqw05nt-o"/><path class="cqbk9ybmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unbound" /></template>
