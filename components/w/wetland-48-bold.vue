<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrlmjdbsl.css';
import '../../css/d/ds62anbdy.css';
import '../../css/z/za_fk3z0n.css';
import '../../css/o/oz5t4ccvy.css';
import '../../css/x/x3rphebkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wrlmjdbsl"/><path class="ds62anbdy"/><path class="za_fk3z0n"/><path class="oz5t4ccvy"/><path class="x3rphebkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wetland-48-bold" /></template>
