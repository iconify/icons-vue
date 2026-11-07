<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_hji6de.css';
import '../../css/r/rhb1k3bmi.css';
import '../../css/i/il6nib2-h.css';
import '../../css/h/hz9qwn3kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="rhb1k3bmi"/><path class="il6nib2-h"/><path class="hz9qwn3kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:traffic-economy-bold-duotone" /></template>
