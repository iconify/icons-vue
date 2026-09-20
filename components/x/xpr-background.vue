<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pqu6i-bhy"/><path clip-rule="evenodd" class="lf1xof33c"/><path class="wpkxh_bcs"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xpr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lf1xof33c {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.436 6.81C14.186 5.925 13.35 4 12.026 4c-1.33 0-2.225 1.825-2.5 2.81c-.19.595-.56 2.09-.61 3.325l-1.63 1.305c-.655-.655-1.87-2.17-1.48-2.955c.39-.79 2.025-.69 2.795-.54l.15-.73C7.466 6.955 4.916 6.89 5 8.74c.11 2.315 2.86 4.355 3.915 5.06c.015.39.09 1.34.275 2.04c-.7.215-2.32.515-3.15 0s.205-2.105.825-2.83l-.55-.58c-.75.83-1.965 2.765-.85 3.88c1.4 1.395 5.375-.105 6.56-.665l1.84.775c-.21.905-.875 2.73-1.84 2.765s-1.6-1.5-1.8-2.275l-.675.24c.21.94 1.005 2.835 2.475 2.85c1.475.015 2.405-2.45 2.685-3.69c.11-.61.33-1.975.36-2.51c.335-.21 1.124-.77 1.625-1.28c.575.565 1.685 1.915 1.53 2.75c-.19 1.04-1.545.88-2.815.725l-.21.75c1.25.275 3.75.375 3.8-1.475c.045-1.855-2.6-4.195-3.93-5.135a12.4 12.4 0 0 0-.275-1.95c.98-.335 3.03-.73 3.42.415c.08.29-.02 1.17-1.06 2.36l.55.575c.704-.77 1.88-2.605.94-3.755c-1.17-1.435-5.23-.32-6.62.565c-.4-.19-1.335-.605-1.89-.725c.175-.88.785-2.68 1.82-2.845c.325-.04 1.145.355 1.795 2.245zM7.87 11.975l.975-.81v1.65zm2.07-3.68l1.18.445l-1.405.83zm4.15.02l.225 1.26l-1.425-.81zm2.055 3.695l-.97.82l-.01-1.65zm-2.05 3.575l-1.2-.385v-.005l1.365-.89zm-4.175.035l1.2-.39l-1.365-.895zM12.016 9L9.5 10.56v2.95L12.016 15l2.485-1.49v-2.95z");
}

.pqu6i-bhy {
  fill: var(--svg-color--7641e4, #7641e4);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wpkxh_bcs {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.002 13a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
