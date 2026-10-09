<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m99dslsql.css';
import '../../css/d/dju16bcaj.css';
import '../../css/q/q5tmzt_ie.css';
import '../../css/v/vq5ukvb_p.css';
import '../../css/v/vg8_g8bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m99dslsql"/><path class="dju16bcaj"/><path class="q5tmzt_ie"/><path class="vq5ukvb_p"/><path class="vg8_g8bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:recycling-bin-48" /></template>
