<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/q/qtyhnfbre.css';
import '../../css/b/b7mby8biq.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG6duoWd3v"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="qtyhnfbre"/><path class="b7mby8biq"/></g></mask></defs><circle mask="url(#SVG6duoWd3v)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:studio-backdrop-circle-filled" /></template>
