<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/v/v1dheebdz.css';
import '../../css/s/sp5_txb5b.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGsSTXr1TV"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="v1dheebdz"/><path class="sp5_txb5b"/></g></mask></defs><circle mask="url(#SVGsSTXr1TV)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:triangle-down-filled-circle-filled" /></template>
