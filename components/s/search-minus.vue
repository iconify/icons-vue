<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olznt6bba.css';
import '../../css/a/augpk_bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olznt6bba"/><path class="augpk_bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:search-minus" /></template>
