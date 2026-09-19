<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmjzbm1yy.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted kmjzbm1yy"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-2--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:network-switch-solid-alerted" /></template>
