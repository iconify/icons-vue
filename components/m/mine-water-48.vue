<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7ezmybgf.css';
import '../../css/e/elzyb5xmp.css';
import '../../css/o/ovlh7zbng.css';
import '../../css/n/nqumikboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r7ezmybgf"/><path class="elzyb5xmp"/><path class="ovlh7zbng"/><path class="nqumikboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mine-water-48" /></template>
