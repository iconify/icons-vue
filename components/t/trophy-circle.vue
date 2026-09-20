<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r10eajbbi.css';
import '../../css/z/z0mykrllt.css';
import '../../css/f/f6u8w3b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r10eajbbi"/><path class="z0mykrllt"/><rect class="f6u8w3b2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:trophy-circle" /></template>
