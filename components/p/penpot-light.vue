<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc3sa0i4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rc3sa0i4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:penpot-light" /></template>
