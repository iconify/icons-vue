<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9unun_6a.css';
import '../../css/q/q5don451u.css';
import '../../css/u/uaycyrbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x9unun_6a"/><path class="q5don451u"/><path class="uaycyrbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tape-drive-solid-alerted" /></template>
