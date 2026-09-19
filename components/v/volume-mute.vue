<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjx7l10uk.css';
import '../../css/a/a0a9vkbzg.css';
import '../../css/a/atjk8mbde.css';
import '../../css/z/z59v0dbaw.css';
import '../../css/e/e_zs6sh3r.css';
import '../../css/d/da1dlqbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<mask id="SVGgeW4OrYP" width="13" height="13" x="30" y="18" maskUnits="userSpaceOnUse" style="mask-type:alpha"><rect class="hjx7l10uk"/></mask><g class="a0a9vkbzg"><g mask="url(#SVGgeW4OrYP)" class="atjk8mbde"><path class="z59v0dbaw"/><path class="e_zs6sh3r"/></g><path class="da1dlqbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:volume-mute" /></template>
