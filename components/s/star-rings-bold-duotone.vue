<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwtm_3btu.css';
import '../../css/m/mdrgupb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dwtm_3btu"/><path class="mdrgupb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-rings-bold-duotone" /></template>
