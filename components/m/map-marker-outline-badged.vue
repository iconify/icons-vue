<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tljd5gb8n.css';
import '../../css/z/z5-1j_thg.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged tljd5gb8n"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged z5-1j_thg"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-3--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:map-marker-outline-badged" /></template>
