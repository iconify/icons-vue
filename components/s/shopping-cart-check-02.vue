<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/w5rrk9v6e.css';
import '../../css/c/c5jc8os8p.css';
import '../../css/o/o50ddxiay.css';
import '../../css/b/b-v3dtbhs.css';
import '../../css/f/fe1mv7ygx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="w5rrk9v6e"/><path class="c5jc8os8p"/><circle class="o50ddxiay"/><circle class="b-v3dtbhs"/><path class="fe1mv7ygx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-cart-check-02" /></template>
