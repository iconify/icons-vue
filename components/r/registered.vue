<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqtgn03gm.css';
import '../../css/w/wu13qac7h.css';
import '../../css/y/yk60_vm2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="tqtgn03gm"><path class="wu13qac7h"/><path class="yk60_vm2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:registered" /></template>
