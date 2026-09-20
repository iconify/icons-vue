<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjzl2sb1x.css';
import '../../css/u/ui2c-mkkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bjzl2sb1x"/><path class="ui2c-mkkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shopping-cart-filled" /></template>
