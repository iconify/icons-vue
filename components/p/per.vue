<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGkOiHGdLu)" class="qps-oachz"/><path fill="url(#SVGJa1tddWr)" class="geg_qw77b"/><path fill="url(#SVGveaLocqZ)" class="rtop3jq0j"/><defs><linearGradient id="SVGkOiHGdLu" x1="18.331" x2="3.919" y1="6.589" y2="14.656" gradientUnits="userSpaceOnUse"><stop class="m8m80lbjp"/><stop offset="1" class="sa9qxxbzd"/></linearGradient><linearGradient id="SVGJa1tddWr" x1="17.513" x2="9.632" y1="3.896" y2="19.709" gradientUnits="userSpaceOnUse"><stop class="h974rh0rd"/><stop offset="1" class="ox97subyi"/></linearGradient><linearGradient id="SVGveaLocqZ" x1="9.783" x2="8.621" y1="17.95" y2="20.738" gradientUnits="userSpaceOnUse"><stop class="eutyfbboq"/><stop offset="1" class="ibvw_sb1j"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:per" /></template>
<style>
.eutyfbboq {
  stop-color: var(--svg-color--fefefc, #fefefc);
}

.ft5dv1b6b {
  fill: none;
}

.geg_qw77b {
  d: path("m3.828 10.251l-.026.288c1.224-1.044 4.29-2.91 7.606-2.91c2.69 0 4.233 1.542 4.665 2.334l-.432 3.405l-4.83 2.664l-.354.272v-6.156a.97.97 0 0 0-1.939 0v8.537a8 8 0 0 0 1.939.617v-1.697c2.5-.329 6.685-1.825 6.685-5.95c0-1.568-1.162-3.266-1.779-3.914l-3.24-.94l-3.646.55l-2.808 1.445z");
}

.h974rh0rd {
  stop-color: var(--svg-color--e67f5e, #e67f5e);
}

.ibvw_sb1j {
  stop-color: var(--svg-color--ffc125, #ffc125);
}

.m8m80lbjp {
  stop-color: var(--svg-color--fd2307, #fd2307);
}

.ox97subyi {
  stop-color: var(--svg-color--fcc252, #fcc252);
}

.qps-oachz {
  d: path("M12 19.457A8.229 8.229 0 1 0 12 3a8.229 8.229 0 0 0 0 16.457");
}

.rtop3jq0j {
  d: path("m3.843 10.05l-.03.258c1.774-1.687 5.07-2.942 7.492-2.942c2.495 0 4.295 1.492 4.295 3.323c0 2.684-3.965 3.96-5.657 4.201V10.2a1.029 1.029 0 1 0-2.057 0v9.771a1.028 1.028 0 1 0 2.057 0v-3.096c6.48-1.532 7.2-4.926 7.2-5.96c0-1.029-.767-4.315-5.514-4.315c-3.435 0-6.402 2.098-7.786 3.45");
}

.sa9qxxbzd {
  stop-color: var(--svg-color--fdb106, #fdb106);
}

</style>
