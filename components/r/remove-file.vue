<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foa7vwb3f.css';
import '../../css/p/puxm9jbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="foa7vwb3f"/><path class="puxm9jbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:remove-file" /></template>
