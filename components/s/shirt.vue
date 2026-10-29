<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sclvgdh2f.css';
import '../../css/w/wbiy0ab6r.css';
import '../../css/u/ucqslnb_h.css';
import '../../css/r/rwx2m4bel.css';
import '../../css/x/xu3qqabgh.css';
import '../../css/b/bip_hp6uy.css';
import '../../css/b/b_8n2rbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sclvgdh2f wm-shadow"/><path class="wbiy0ab6r wm-k"/><path class="ucqslnb_h wm-k"/><path class="rwx2m4bel wm-k"/><path class="wm-k xu3qqabgh"/><path class="bip_hp6uy wm-k"/><path class="b_8n2rbkk wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:shirt" /></template>
