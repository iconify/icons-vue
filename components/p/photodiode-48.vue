<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5_6-abcl.css';
import '../../css/o/of1wzvb1f.css';
import '../../css/o/oef6x1_vi.css';
import '../../css/e/ekxhm6afd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y5_6-abcl"/><path class="of1wzvb1f"/><path class="oef6x1_vi"/><path class="ekxhm6afd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:photodiode-48" /></template>
