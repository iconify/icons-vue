<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvvpbts5o.css';
import '../../css/t/txrxn8dlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="cvvpbts5o"/><path class="txrxn8dlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nixos-wordmark" /></template>
