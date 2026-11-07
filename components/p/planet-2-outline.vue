<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb99incev.css';
import '../../css/l/loow9ybwq.css';
import '../../css/o/ocn83zybz.css';
import '../../css/a/a453s8nfz.css';
import '../../css/n/n1grccb5d.css';
import '../../css/o/onsgwijlx.css';
import '../../css/u/uthzbm34d.css';
import '../../css/f/fjawlt9ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb99incev"/><path class="loow9ybwq"/><path clip-rule="evenodd" class="ocn83zybz"/><path class="a453s8nfz"/><path class="n1grccb5d"/><path class="onsgwijlx"/><path class="uthzbm34d"/><path class="fjawlt9ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-2-outline" /></template>
