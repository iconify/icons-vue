<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdjiz7b1s.css';
import '../../css/t/tx7dcyx9v.css';
import '../../css/k/k-6z9bsqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdjiz7b1s"/><path class="tx7dcyx9v"/><path class="k-6z9bsqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-camera-bold-duotone" /></template>
