<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_09tab4h.css';
import '../../css/c/c807_0blv.css';
import '../../css/n/ns1f0lben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_09tab4h"/><path class="c807_0blv"/><path class="ns1f0lben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:viva-engage-logo" /></template>
