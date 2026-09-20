<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnl2_bcrh.css';
import '../../css/f/flf8qs4fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnl2_bcrh"/><path class="flf8qs4fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:twtich" /></template>
