<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr7_wabhq.css';
import '../../css/r/r3nawdb_c.css';
import '../../css/o/ok5c6eb9i.css';
import '../../css/h/h_rhu0bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tr7_wabhq"/><path class="r3nawdb_c"/><path class="ok5c6eb9i"/><path class="h_rhu0bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:taxi-20" /></template>
