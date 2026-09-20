<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0gx-2k1c.css';
import '../../css/s/slvmq7bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="k0gx-2k1c"/><path clip-rule="evenodd" class="slvmq7bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinepods-light" /></template>
