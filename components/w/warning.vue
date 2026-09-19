<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xamtaihib.css';
import '../../css/b/bc70y0nuy.css';
import '../../css/o/oqexibvmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xamtaihib"/><circle class="bc70y0nuy"/><path class="oqexibvmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:warning" /></template>
