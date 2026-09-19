<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bg0l67o0u.css';
import '../../css/o/o50ddxiay.css';
import '../../css/b/b-v3dtbhs.css';
import '../../css/f/fe1mv7ygx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bg0l67o0u"/><circle class="o50ddxiay"/><circle class="b-v3dtbhs"/><path class="fe1mv7ygx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-cart-add-02" /></template>
