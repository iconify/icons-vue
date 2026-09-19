<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ns9rbyk.css';
import '../../css/a/as60m0h-n.css';
import '../../css/o/o_aledblo.css';
import '../../css/n/nuec0m2ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1ns9rbyk"/><path class="as60m0h-n"/><path class="o_aledblo"/><path class="nuec0m2ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:quantum-engine" /></template>
