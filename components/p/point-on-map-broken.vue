<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gljrr8bsg.css';
import '../../css/q/q_nyagb1l.css';
import '../../css/u/uxykybyxi.css';
import '../../css/p/ptvu1u_4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gljrr8bsg"/><path class="q_nyagb1l"/><path class="uxykybyxi"/><circle class="ptvu1u_4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:point-on-map-broken" /></template>
