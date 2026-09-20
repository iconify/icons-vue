<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/o/o_zgl7bku.css';
import '../../css/z/zgryikxog.css';
import '../../css/b/bd9gczbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGY21vecDi"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="o_zgl7bku"/><path class="zgryikxog"/></g></mask></defs><circle mask="url(#SVGY21vecDi)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:photo-camera-circle-filled" /></template>
