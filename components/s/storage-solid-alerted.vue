<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jghac8mdu.css';
import '../../css/q/qy7dv0tza.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted jghac8mdu"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-2--alerted qy7dv0tza"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:storage-solid-alerted" /></template>
