<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvbx92bci.css';
import '../../css/t/ttjr82jtr.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged dvbx92bci"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-2--badged ttjr82jtr"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:storage-solid-badged" /></template>
