<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGwTNrCbvV)" class="fervuaccm"/><defs><linearGradient id="SVGwTNrCbvV" x1="19.664" x2="4.524" y1="17.186" y2="6.624" gradientUnits="userSpaceOnUse"><stop class="eb3dhob6x"/><stop offset=".49" class="zr29kub0k"/><stop offset="1" class="lbbflt1mw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ufi" /></template>
<style>
.eb3dhob6x {
  stop-color: var(--svg-color--7000ff, #7000ff);
}

.fervuaccm {
  d: path("m8.933 3.536l8.909 9.73L7.235 4.352l-.433.292l10.72 8.999l-12.15-7.745a7 7 0 0 0-.337.383l12.215 7.784L3.984 7.878c-.079.146-.146.292-.22.45l13.274 6.186l-13.864-4.37l-.09.495l13.807 4.353L3 12.552l.045.511l13.756 2.43l-13.34-.585c.056.169.124.343.191.506l13.127.58l-12.244 1.068l.338.473l11.95-1.047l-10.685 2.374c.169.135.338.27.506.393l10.292-2.277l-8.773 3.194c.225.101.45.197.686.281l8.256-3.003l-6.62 3.448q.438.067.883.1l5.962-3.104l-4.387 3.077a10 10 0 0 0 1.153-.197l3.526-2.475l-2.25 2.064a9 9 0 0 0 1.868-1.029l.72-.663l-.253.303A8.99 8.99 0 0 0 20.63 9.47l-.112 2.615l-.332-3.813a8 8 0 0 0-.596-1.097l.433 4.95l-1.372-6.176c-.209-.225-.428-.45-.653-.652l1.536 6.94l-2.891-7.942a8 8 0 0 0-.664-.365l3.082 8.475l-4.73-9.1a13 13 0 0 0-.64-.146l4.926 9.477l-6.743-9.634a7 7 0 0 0-.59.028l6.928 9.898l-8.762-9.56q-.264.075-.518.168");
}

.ft5dv1b6b {
  fill: none;
}

.lbbflt1mw {
  stop-color: var(--svg-color--ffbf1c, #ffbf1c);
}

.zr29kub0k {
  stop-color: var(--svg-color--00ffd1, #00ffd1);
}

</style>
