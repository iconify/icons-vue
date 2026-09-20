<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxacudx8p.css';
import '../../css/s/s4p2gkl9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pxacudx8p"/><path class="s4p2gkl9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:phonecall-receive-solid" /></template>
