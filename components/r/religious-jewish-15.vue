<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btcpoi1uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="btcpoi1uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:religious-jewish-15" /></template>
