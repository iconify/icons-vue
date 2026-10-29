<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qar66zblb.css';
import '../../css/v/vn3ejy6yj.css';
import '../../css/a/a_miq4bhp.css';
import '../../css/i/i10thab8l.css';
import '../../css/l/ltxj3vb3r.css';
import '../../css/t/t4q9hwpzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qar66zblb wm-shadow"/><path class="vn3ejy6yj wm-k"/><path class="a_miq4bhp wm-k"/><path class="i10thab8l wm-k"/><path class="ltxj3vb3r wm-k"/><path class="t4q9hwpzk wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:type" /></template>
