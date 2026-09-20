<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is_bib.css';
import '../../css/y/ydovum.css';
import '../../css/r/rek8ly.css';
import '../../css/d/d_veic.css';
import '../../css/d/d-g-t0ye.css';
import '../../css/d/d-u2wfvb.css';
import '../../css/d/d-tpcgta.css';
import '../../css/d/d-y53qgi.css';
import '../../css/d/d-ysi9rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is_bib ydovum"/><path class="rek8ly ydovum"/><path class="d_veic ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:pleroma" /></template>
