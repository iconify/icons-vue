<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-ovh_4-p.css';
import '../../css/j/jst_e4bic.css';
import '../../css/q/q9zua8b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n-ovh_4-p"/><path class="jst_e4bic"/><path class="q9zua8b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:salt-cavern-20" /></template>
