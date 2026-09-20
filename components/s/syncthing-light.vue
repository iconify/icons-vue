<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg8zxbl_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mg8zxbl_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:syncthing-light" /></template>
