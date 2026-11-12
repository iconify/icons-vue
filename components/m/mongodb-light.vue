<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0nj5mbku.css';
import '../../css/z/zs9x5hotx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k0nj5mbku"/><path class="zs9x5hotx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mongodb-light" /></template>
