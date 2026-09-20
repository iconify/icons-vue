<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="s6w8hobqx"/><path class="ic3i3xh9w"/><path class="z6ulu3bwi"/><path class="eduul7b8v"/><path class="qmduz5b0b"/><path class="em4qq-b7f"/><path class="w18c2nb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:motor-boat" /></template>
<style>
.eduul7b8v {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M7.248 19.101C10.798 16.41 14 16.043 15 16.043V20c0 3.162-7.752-.899-7.752-.899");
}

.em4qq-b7f {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M7 23.817c4 2.292 26 1.146 26 1.146s.288-2.335-.24-4.206L2.078 19.589c.977 1.205 2.614 2.905 4.922 4.228");
}

.ic3i3xh9w {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M32 18h2v7h-2z");
}

.qmduz5b0b {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M33 24.964s.5-4.013-1-5.731L1 18.086s2 3.439 6 5.732c4 2.291 26 1.146 26 1.146");
}

.s6w8hobqx {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M35 19a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1z");
}

.w18c2nb2x {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M0 24h36v12H0z");
}

.z6ulu3bwi {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M6 19.219S11 15 16 15h.029L16 20s0 1-4 1s-6-1.781-6-1.781");
}

</style>
