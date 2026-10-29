<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2ch6-ban.css';
import '../../css/k/kmvltdbhh.css';
import '../../css/m/mx_g6rb3q.css';
import '../../css/w/wgjztzbms.css';
import '../../css/c/czugqwb_p.css';
import '../../css/r/rrp9v8czq.css';
import '../../css/i/irft7ub_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2ch6-ban wm-shadow"/><path class="kmvltdbhh wm-k"/><path class="mx_g6rb3q wm-k"/><path class="wgjztzbms wm-k"/><path class="czugqwb_p wm-k"/><path class="rrp9v8czq wm-shine"/><path class="irft7ub_b wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:subscript" /></template>
